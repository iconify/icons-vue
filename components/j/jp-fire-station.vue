<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5dad0fgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g5dad0fgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:jp-fire-station" /></template>
