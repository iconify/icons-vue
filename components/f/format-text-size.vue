<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kcecrokwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="kcecrokwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:format-text-size" /></template>
