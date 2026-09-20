<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6s6g16ad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n6s6g16ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:image-layout-frameless" /></template>
