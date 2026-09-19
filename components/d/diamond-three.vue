<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz5lfebzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uz5lfebzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:diamond-three" /></template>
