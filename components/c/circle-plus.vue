<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uje9hhbpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uje9hhbpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-plus" /></template>
