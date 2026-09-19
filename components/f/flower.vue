<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdi43l57p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":416,"height":480};
const content = `<path class="vdi43l57p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:flower" /></template>
