<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgbwi1bgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":666,"height":680};
const content = `<path class="sgbwi1bgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:full" /></template>
