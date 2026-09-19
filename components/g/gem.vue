<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbu41_9ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="cbu41_9ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:gem" /></template>
