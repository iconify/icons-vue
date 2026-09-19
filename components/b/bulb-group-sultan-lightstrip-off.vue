<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqae0sbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zqae0sbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bulb-group-sultan-lightstrip-off" /></template>
