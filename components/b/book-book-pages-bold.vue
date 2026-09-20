<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j33nzxbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j33nzxbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:book-book-pages-bold" /></template>
