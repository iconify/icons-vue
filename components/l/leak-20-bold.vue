<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b146zkmak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b146zkmak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:leak-20-bold" /></template>
