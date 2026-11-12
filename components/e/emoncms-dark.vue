<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq7gawjkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zq7gawjkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:emoncms-dark" /></template>
