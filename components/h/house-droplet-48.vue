<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvggpac7z.css';
import '../../css/w/wracacbgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wvggpac7z"/><path class="wracacbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-droplet-48" /></template>
