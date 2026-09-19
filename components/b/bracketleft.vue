<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2n0ttdhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":168,"height":954};
const content = `<path class="c2n0ttdhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bracketleft" /></template>
