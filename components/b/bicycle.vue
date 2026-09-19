<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6mmipbdo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":922,"height":622};
const content = `<path class="g6mmipbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:bicycle" /></template>
