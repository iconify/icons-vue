<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3suvebfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a3suvebfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:drink-bottle-and-milk-carton-and-can" /></template>
