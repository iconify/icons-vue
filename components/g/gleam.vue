<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5tfq2sjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a5tfq2sjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:gleam" /></template>
