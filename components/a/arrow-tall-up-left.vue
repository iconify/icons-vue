<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn-5w0b6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="fn-5w0b6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:arrow-tall-up-left" /></template>
