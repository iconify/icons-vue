<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5e21pb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="p5e21pb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:barchartdesc" /></template>
