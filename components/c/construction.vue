<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_cr_6bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v_cr_6bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:construction" /></template>
