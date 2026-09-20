<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kzleqd5vl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzleqd5vl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:barcode-line" /></template>
