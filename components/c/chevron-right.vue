<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpylyqj_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="tpylyqj_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:chevron-right" /></template>
