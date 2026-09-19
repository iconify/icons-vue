<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3c_ovw8n.css';
import '../../css/w/w8rkv-bcn.css';
import '../../css/s/s8m5ot9tn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g3c_ovw8n"/><path class="w8rkv-bcn"/><path class="s8m5ot9tn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-refinery" /></template>
