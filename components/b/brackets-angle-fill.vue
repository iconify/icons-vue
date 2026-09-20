<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkvp_mb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkvp_mb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:brackets-angle-fill" /></template>
