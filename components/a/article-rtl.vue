<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x16refvya.css';
import '../../css/a/a9mph4b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="x16refvya"/><path class="a9mph4b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-rtl" /></template>
