<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z7ycpab4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z7ycpab4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:fighter-jet" /></template>
