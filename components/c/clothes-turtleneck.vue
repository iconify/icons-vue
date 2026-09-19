<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bg1s_bx-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bg1s_bx-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:clothes-turtleneck" /></template>
