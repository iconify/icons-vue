<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kjn7jibdx.css';
import '../../css/x/xd_e_q94j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kjn7jibdx"/><path class="xd_e_q94j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-add" /></template>
