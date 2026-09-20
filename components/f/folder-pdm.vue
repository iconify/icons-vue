<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hx9qcfbri.css';
import '../../css/e/ewlo7db9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hx9qcfbri"/><path class="ewlo7db9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-pdm" /></template>
