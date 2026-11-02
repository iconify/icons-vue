<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq3pbd0ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq3pbd0ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:decimals-arrow-left-line" /></template>
