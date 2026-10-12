<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fel8-rbzx.css';
import '../../css/g/ghwlb4bnj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fel8-rbzx"/><path class="ghwlb4bnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:lock-stroke-20" /></template>
