<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j59i0pbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j59i0pbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folding-fan-fill" /></template>
