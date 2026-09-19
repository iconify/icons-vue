<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j57b6uxil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="j57b6uxil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:arrow-turn-down" /></template>
