<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhin5jgof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jhin5jgof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:firefox-original" /></template>
