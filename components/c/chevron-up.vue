<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pmpj2ppka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="pmpj2ppka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:chevron-up" /></template>
