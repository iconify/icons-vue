<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncfo34pcr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2304,"height":1280};
const content = `<path class="ncfo34pcr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:battery-2" /></template>
