<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al5fry1wp.css';
import '../../css/e/eremc1y7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="al5fry1wp"/><path class="eremc1y7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:book-marked-20-bold" /></template>
