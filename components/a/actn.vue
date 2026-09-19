<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqy7qnh-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kqy7qnh-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:actn" /></template>
