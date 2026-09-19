<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho7oyvzjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ho7oyvzjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-tumblr" /></template>
