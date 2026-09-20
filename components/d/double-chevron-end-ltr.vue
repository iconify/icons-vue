<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4d1tub4s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e4d1tub4s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:double-chevron-end-ltr" /></template>
