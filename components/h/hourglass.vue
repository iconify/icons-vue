<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qy5ry8bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qy5ry8bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hourglass" /></template>
