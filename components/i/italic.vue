<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm0l__b7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="rm0l__b7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:italic" /></template>
