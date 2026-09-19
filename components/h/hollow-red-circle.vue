<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s5j38abkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="s5j38abkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:hollow-red-circle" /></template>
