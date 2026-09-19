<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5hhus5xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="a5hhus5xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:bullseye" /></template>
