<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-dao-bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":408,"height":384};
const content = `<path class="g-dao-bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:long-arrow-return" /></template>
