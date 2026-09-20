<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuzmv5bfi.css';
import '../../css/m/m3ckqtbim.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uuzmv5bfi"/><path class="m3ckqtbim"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:articles-search-rtl" /></template>
