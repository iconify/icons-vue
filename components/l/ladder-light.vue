<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th995e03e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="th995e03e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ladder-light" /></template>
