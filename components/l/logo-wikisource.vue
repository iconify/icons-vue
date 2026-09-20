<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojls-ccqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ojls-ccqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-wikisource" /></template>
