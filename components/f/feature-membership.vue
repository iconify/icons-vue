<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr1e2hb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qr1e2hb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:feature-membership" /></template>
