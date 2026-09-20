<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl9vqoues.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="zl9vqoues"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:definition-search-book-solid" /></template>
