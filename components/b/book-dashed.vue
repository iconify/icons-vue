<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bqgy42bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqgy42bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:book-dashed" /></template>
