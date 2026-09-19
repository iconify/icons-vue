<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f4ceoj48v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f4ceoj48v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:gzr" /></template>
