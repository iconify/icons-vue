<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywsqx8bpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ywsqx8bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:eyedropper" /></template>
