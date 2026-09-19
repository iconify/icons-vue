<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzvqbubgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzvqbubgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:home-heart-filled" /></template>
