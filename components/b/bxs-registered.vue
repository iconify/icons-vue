<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0jxknbfz.css';
import '../../css/j/jmjky1e4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0jxknbfz"/><path class="jmjky1e4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-registered" /></template>
