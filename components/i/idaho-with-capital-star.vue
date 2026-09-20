<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn3q1p62s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="hn3q1p62s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:idaho-with-capital-star" /></template>
