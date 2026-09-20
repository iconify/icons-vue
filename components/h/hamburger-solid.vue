<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1q6vab0n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f1q6vab0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:hamburger-solid" /></template>
