<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5q2pxb9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="g5q2pxb9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:cloud-upload-fill" /></template>
