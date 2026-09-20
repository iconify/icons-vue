<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyu5p-s8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kyu5p-s8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-with-euro" /></template>
