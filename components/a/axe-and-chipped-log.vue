<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh_a1ub3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="wh_a1ub3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:axe-and-chipped-log" /></template>
