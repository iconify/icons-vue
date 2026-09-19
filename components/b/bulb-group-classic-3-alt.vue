<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j01_ov-ho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j01_ov-ho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-classic-3-alt" /></template>
