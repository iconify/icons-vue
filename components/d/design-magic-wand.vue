<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jm1my-bgj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jm1my-bgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:design-magic-wand" /></template>
