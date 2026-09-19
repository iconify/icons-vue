<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pcj9e0oij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pcj9e0oij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:hands-holding" /></template>
