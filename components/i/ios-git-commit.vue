<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koxdjkbqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="koxdjkbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-git-commit" /></template>
