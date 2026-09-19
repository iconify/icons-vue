<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1774m7wa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y1774m7wa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:bowling" /></template>
