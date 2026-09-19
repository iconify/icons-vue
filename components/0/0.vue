<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p1iksibdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":502,"height":772};
const content = `<path class="p1iksibdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:0" /></template>
