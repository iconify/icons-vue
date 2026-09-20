<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpt9bf_hq.css';
import '../../css/f/f32uk7b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fpt9bf_hq"/><path class="f32uk7b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:glowing-star" /></template>
