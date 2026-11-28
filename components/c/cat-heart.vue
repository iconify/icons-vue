<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ludb6qbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ludb6qbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cat-heart" /></template>
