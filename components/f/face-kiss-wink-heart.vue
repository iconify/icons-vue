<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmdx1rbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dmdx1rbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-kiss-wink-heart" /></template>
