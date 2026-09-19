<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqb09mbio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jqb09mbio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:file-image-fill-12" /></template>
