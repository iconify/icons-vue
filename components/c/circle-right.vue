<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yj2l8ebrt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yj2l8ebrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:circle-right" /></template>
