<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zro8_s1yz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zro8_s1yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ironing-1-filled" /></template>
