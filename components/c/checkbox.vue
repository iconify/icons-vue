<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z446gtb2l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z446gtb2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:checkbox" /></template>
