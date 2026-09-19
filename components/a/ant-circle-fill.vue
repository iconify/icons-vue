<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdp7gyb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="kdp7gyb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:ant-circle-fill" /></template>
