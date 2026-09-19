<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp803d-2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp803d-2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:loyalty-card-barcode-filled" /></template>
