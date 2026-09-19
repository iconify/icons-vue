<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-g0x1_9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c-g0x1_9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:bag-add-outline" /></template>
