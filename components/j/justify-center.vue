<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1nm7_b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d1nm7_b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:justify-center" /></template>
