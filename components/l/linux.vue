<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shoozsbwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="shoozsbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:linux" /></template>
