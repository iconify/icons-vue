<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6g4r_b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6g4r_b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:card-refund-fill" /></template>
