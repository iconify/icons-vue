<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxgsmd1pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uxgsmd1pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:black-large-square" /></template>
