<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_61yfbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c_61yfbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:chat-left-fill" /></template>
