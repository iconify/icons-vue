<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7t1_jb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t7t1_jb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:book-open-stroke-12" /></template>
