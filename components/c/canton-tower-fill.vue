<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp7sqsb5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qp7sqsb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:canton-tower-fill" /></template>
