<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/towrglb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="towrglb_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="osmic:entrance-14" /></template>
