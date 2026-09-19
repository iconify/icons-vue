<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yru3o0c9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yru3o0c9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:codepen" /></template>
