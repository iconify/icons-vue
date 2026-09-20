<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmp48sblm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bmp48sblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbdo-light" /></template>
