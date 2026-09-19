<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v02upobzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v02upobzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:arrows-split-up-and-left" /></template>
