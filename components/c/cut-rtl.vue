<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zphvvzb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zphvvzb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:cut-rtl" /></template>
