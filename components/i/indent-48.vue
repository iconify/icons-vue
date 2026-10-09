<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0pce5fyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z0pce5fyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:indent-48" /></template>
