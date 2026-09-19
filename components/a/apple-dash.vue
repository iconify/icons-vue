<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x06e9_b2c.css';
import '../../css/x/xg13r0bpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x06e9_b2c"/><path class="xg13r0bpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:apple-dash" /></template>
