<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/batb0rb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="batb0rb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-disambiguation-rtl" /></template>
