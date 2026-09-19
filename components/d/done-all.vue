<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt--b6bfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vt--b6bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:done-all" /></template>
