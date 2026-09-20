<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvcqaccok.css';
import '../../css/j/jhhyfu85f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uvcqaccok"/><path class="jhhyfu85f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-books-2" /></template>
