<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6t7jkbzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="k6t7jkbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:file-pdf" /></template>
