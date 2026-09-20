<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wc3om3dtg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wc3om3dtg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hand-point-up" /></template>
