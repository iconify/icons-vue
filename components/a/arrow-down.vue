<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urvau44ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="urvau44ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:arrow-down" /></template>
