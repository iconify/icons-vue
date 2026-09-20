<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr-v_wbjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="jr-v_wbjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:heart-cross" /></template>
