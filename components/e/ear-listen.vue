<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km7n7_jaf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="km7n7_jaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:ear-listen" /></template>
