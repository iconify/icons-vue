<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-3m0x4_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l-3m0x4_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:lamp" /></template>
