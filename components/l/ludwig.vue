<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ch81kq1xx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ch81kq1xx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:ludwig" /></template>
