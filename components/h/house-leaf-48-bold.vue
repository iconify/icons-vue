<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfpjugbvy.css';
import '../../css/z/zrlwepbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vfpjugbvy"/><path class="zrlwepbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:house-leaf-48-bold" /></template>
