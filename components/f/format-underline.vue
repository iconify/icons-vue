<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r3-93rb1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="r3-93rb1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zondicons:format-underline" /></template>
