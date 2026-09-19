<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmgzq2rae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="fmgzq2rae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:heart" /></template>
