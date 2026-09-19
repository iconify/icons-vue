<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwoki8b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hwoki8b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:chevron-down-round" /></template>
