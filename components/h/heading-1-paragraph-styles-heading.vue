<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rq2yzttin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="rq2yzttin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:heading-1-paragraph-styles-heading" /></template>
