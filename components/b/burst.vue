<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ifi7i0bji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ifi7i0bji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:burst" /></template>
