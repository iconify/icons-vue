<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a6c2uebib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a6c2uebib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:brick-wall-with-battlement-and-sallyport" /></template>
