<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gun8es9ig.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gun8es9ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:brightness-high-fill" /></template>
