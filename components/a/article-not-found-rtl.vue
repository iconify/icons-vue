<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oikpp_b-d.css';
import '../../css/a/a9mph4b6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="oikpp_b-d"/><path class="a9mph4b6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-not-found-rtl" /></template>
