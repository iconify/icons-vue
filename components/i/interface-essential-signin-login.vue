<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eckid59_t.css';
import '../../css/t/tc-l81vik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eckid59_t"/><path class="tc-l81vik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-signin-login" /></template>
