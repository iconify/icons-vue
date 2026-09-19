<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4vxbbbrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="u4vxbbbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:hospital-bed" /></template>
