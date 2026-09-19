<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/it526ibql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":1024};
const content = `<path class="it526ibql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:cocktail" /></template>
