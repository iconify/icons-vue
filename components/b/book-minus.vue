<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf2j8ceay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf2j8ceay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:book-minus" /></template>
