<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5bk0tb5p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="p5bk0tb5p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:grinningfacewithonelargeandoneeye" /></template>
