<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h26d6rbnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="h26d6rbnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:audiooff" /></template>
