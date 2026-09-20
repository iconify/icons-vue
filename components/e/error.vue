<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_gx42ena.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w_gx42ena"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:error" /></template>
