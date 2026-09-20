<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op8cfac-b.css';
import '../../css/f/fc86yboyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="op8cfac-b"/><path class="fc86yboyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bald" /></template>
