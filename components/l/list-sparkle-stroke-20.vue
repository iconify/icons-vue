<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt4h9mb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tt4h9mb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:list-sparkle-stroke-20" /></template>
