<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjasth-5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjasth-5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:globe-3-fill" /></template>
