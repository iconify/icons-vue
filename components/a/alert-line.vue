<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvoa-jc4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zvoa-jc4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:alert-line" /></template>
