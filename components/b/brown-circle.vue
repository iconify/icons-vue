<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n00tqpdwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n00tqpdwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:brown-circle" /></template>
