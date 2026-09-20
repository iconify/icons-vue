<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr7bvf8cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cr7bvf8cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:crane-hook-16" /></template>
