<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ezy1ainvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ezy1ainvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-r" /></template>
