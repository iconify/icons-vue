<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w76bybb2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="w76bybb2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:accusoft" /></template>
