<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9kwnk-6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="b9kwnk-6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:lasso-polygon" /></template>
