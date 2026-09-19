<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fee0lt8cu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fee0lt8cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:bowling-ball" /></template>
