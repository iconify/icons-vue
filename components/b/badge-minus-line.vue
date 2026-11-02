<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7h_ksqpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7h_ksqpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:badge-minus-line" /></template>
