<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn2wu3b2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rn2wu3b2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:lyft" /></template>
