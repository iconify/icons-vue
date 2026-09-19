<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7ld8jb4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":24};
const content = `<path class="l7ld8jb4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:bookmark" /></template>
