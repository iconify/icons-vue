<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bn5r7ybyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bn5r7ybyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:circleci" /></template>
