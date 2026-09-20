<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh29bfbue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eh29bfbue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:browser-window-open" /></template>
