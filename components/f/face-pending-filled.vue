<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jp_dy82bb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jp_dy82bb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:face-pending-filled" /></template>
