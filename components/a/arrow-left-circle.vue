<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4prvz4vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z4prvz4vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:arrow-left-circle" /></template>
