<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmbmllbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zmbmllbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:interface-content-book-open-content-books-book-open" /></template>
