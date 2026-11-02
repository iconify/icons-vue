<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1q_0bcvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1q_0bcvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-branch-minus-line" /></template>
