<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5r3edbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5r3edbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:bullet-list" /></template>
