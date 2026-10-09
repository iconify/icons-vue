<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvggpac7z.css';
import '../../css/s/ssy7ypbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvggpac7z"/><path class="ssy7ypbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-flame-48" /></template>
