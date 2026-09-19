<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_c48qb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":480,"height":496};
const content = `<path class="h_c48qb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:copy" /></template>
