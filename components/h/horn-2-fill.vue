<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr2540bcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qr2540bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:horn-2-fill" /></template>
