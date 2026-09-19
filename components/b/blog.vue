<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu1n0r_6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="cu1n0r_6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:blog" /></template>
