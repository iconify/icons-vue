<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6geo1bkk.css';
import '../../css/d/drbv3ibqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h6geo1bkk"/><path class="drbv3ibqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:chat" /></template>
