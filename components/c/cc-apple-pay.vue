<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_zvdpf8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j_zvdpf8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:cc-apple-pay" /></template>
