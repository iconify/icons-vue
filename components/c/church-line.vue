<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8c_3ccqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8c_3ccqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:church-line" /></template>
