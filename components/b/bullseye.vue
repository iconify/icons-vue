<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ybh5y4q9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ybh5y4q9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:bullseye" /></template>
