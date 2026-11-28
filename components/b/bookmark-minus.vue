<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1cputbqh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1cputbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bookmark-minus" /></template>
