<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6jd9_b7p.css';
import '../../css/b/bvgd0jb0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j6jd9_b7p"/><path class="bvgd0jb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:crane-hook-20-bold" /></template>
