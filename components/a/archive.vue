<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmiyzeyex.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1536};
const content = `<path class="bmiyzeyex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:archive" /></template>
