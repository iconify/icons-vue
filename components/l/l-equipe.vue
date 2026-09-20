<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zdv_r9b4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zdv_r9b4w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:l-equipe" /></template>
