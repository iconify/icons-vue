<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3rydq38c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="d3rydq38c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:angry" /></template>
