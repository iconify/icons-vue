<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uabmklxbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="uabmklxbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:gaming-11" /></template>
