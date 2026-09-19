<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8v77ac5n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="c8v77ac5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:glimmer" /></template>
