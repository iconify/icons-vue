<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ot8ud_bdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="ot8ud_bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:electronics-14" /></template>
