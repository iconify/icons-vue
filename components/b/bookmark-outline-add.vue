<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a8txeybqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="a8txeybqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:bookmark-outline-add" /></template>
