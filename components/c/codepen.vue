<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcgn157ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcgn157ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:codepen" /></template>
