<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8goq-vxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="d8goq-vxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:chart-pie" /></template>
