<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3_i3uapp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="u3_i3uapp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:double-curly-loop" /></template>
