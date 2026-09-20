<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et8-vkb0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="et8-vkb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hand-holding-heart" /></template>
