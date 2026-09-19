<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvndipqdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lvndipqdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:line-social-fill-16" /></template>
