<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqc5o4bpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dqc5o4bpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:eye-arrow-right-outline" /></template>
