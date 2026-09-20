<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by6j3h99l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="by6j3h99l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:bird-and-question-mark" /></template>
