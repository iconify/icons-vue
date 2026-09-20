<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-x7yjbqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="i-x7yjbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:certificate-exclamation-filled" /></template>
