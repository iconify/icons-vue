<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfw4b_blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wfw4b_blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:horizontal-bar" /></template>
