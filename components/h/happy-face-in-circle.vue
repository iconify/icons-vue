<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1bue927j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="c1bue927j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:happy-face-in-circle" /></template>
