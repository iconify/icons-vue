<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbch5l7zf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nbch5l7zf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-line-icons:graph" /></template>
