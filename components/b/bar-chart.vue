<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9kryfb_n.css';
import '../../css/e/ed5g3xh8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p9kryfb_n"/><path class="ed5g3xh8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bar-chart" /></template>
