<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p41_2drfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="p41_2drfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:instagram" /></template>
