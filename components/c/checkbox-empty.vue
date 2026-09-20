<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llf2_5bts.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="llf2_5bts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:checkbox-empty" /></template>
