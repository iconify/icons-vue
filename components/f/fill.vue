<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5b6qmb6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="c5b6qmb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:fill" /></template>
