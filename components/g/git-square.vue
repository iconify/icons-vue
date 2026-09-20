<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aawif9bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aawif9bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:git-square" /></template>
