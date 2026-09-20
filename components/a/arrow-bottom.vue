<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/faps_v1gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="faps_v1gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:arrow-bottom" /></template>
