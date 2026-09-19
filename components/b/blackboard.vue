<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_8gf-byn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o_8gf-byn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:blackboard" /></template>
