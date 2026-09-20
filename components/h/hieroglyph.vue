<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zykmb7b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zykmb7b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:hieroglyph" /></template>
