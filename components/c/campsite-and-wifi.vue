<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8mc_4l0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="g8mc_4l0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-and-wifi" /></template>
