<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc8bdhb2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc8bdhb2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:axis3d" /></template>
