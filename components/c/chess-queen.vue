<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zu-vsqb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zu-vsqb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:chess-queen" /></template>
