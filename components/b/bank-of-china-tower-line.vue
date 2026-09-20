<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/znt4c7btl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="znt4c7btl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bank-of-china-tower-line" /></template>
