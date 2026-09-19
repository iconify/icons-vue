<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qan8l4b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qan8l4b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cloud-filled" /></template>
