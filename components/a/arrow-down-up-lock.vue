<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqirs8qrr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cqirs8qrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-down-up-lock" /></template>
