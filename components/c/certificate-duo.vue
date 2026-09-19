<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr11d0b7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="qr11d0b7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:certificate-duo" /></template>
