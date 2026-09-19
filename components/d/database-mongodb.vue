<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p6q5h5ycr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="p6q5h5ycr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:database-mongodb" /></template>
