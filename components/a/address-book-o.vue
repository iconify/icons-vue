<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6yd1sbvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1792};
const content = `<path class="s6yd1sbvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:address-book-o" /></template>
