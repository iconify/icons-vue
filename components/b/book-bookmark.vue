<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co9wg_bom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="co9wg_bom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:book-bookmark" /></template>
