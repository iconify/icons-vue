<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/irx53ppki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="irx53ppki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:halo" /></template>
