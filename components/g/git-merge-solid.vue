<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-tp1gbmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="l-tp1gbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:git-merge-solid" /></template>
