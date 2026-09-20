<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8fcheflj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="p8fcheflj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:bookmark-2-16" /></template>
