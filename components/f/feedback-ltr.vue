<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-uyyjz3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k-uyyjz3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:feedback-ltr" /></template>
