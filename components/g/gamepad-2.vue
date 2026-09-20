<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmc1m3ixj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmc1m3ixj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:gamepad-2" /></template>
