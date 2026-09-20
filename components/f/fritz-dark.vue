<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4xee55nr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w4xee55nr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:fritz-dark" /></template>
