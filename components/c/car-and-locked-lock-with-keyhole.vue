<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qdcorkbbz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qdcorkbbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:car-and-locked-lock-with-keyhole" /></template>
