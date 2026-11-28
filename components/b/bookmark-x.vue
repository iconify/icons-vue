<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byamri8or.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byamri8or"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bookmark-x" /></template>
