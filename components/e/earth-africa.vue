<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/widzzbbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="widzzbbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:earth-africa" /></template>
