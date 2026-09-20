<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sjxclds3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sjxclds3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:article-check" /></template>
