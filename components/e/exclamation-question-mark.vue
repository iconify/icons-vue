<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt-vn2f_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rt-vn2f_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:exclamation-question-mark" /></template>
