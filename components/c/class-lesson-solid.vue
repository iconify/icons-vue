<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jervz5bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jervz5bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:class-lesson-solid" /></template>
