<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4g5aej_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="p4g5aej_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-ltr" /></template>
