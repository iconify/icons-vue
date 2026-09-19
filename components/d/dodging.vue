<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1my9l8uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u1my9l8uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:dodging" /></template>
