<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5ajk8big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r5ajk8big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:chevron-right-circle" /></template>
