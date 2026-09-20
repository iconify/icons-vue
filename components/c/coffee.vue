<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xpwnv1bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xpwnv1bou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:coffee" /></template>
