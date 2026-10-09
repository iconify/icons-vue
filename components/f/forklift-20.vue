<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmeg1tr8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mmeg1tr8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:forklift-20" /></template>
