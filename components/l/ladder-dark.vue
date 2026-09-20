<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d9187bsnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d9187bsnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ladder-dark" /></template>
