<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqfa2vbfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="tqfa2vbfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:accessible-icon" /></template>
