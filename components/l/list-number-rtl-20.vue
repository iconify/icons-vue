<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i3vocxb4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i3vocxb4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-number-rtl-20" /></template>
