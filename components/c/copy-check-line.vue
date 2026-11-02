<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmv8chbej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmv8chbej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copy-check-line" /></template>
