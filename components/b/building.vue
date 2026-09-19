<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-2d8gbdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":607,"height":696};
const content = `<path class="w-2d8gbdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:building" /></template>
