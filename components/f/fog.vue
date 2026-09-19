<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr7vsjalr.css';
import '../../css/s/s0goipb0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qr7vsjalr"/><rect class="s0goipb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fog" /></template>
