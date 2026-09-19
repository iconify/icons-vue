<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq4vo4zge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq4vo4zge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bowl-noodles-alt" /></template>
