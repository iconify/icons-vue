<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r4bvc2biz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="r4bvc2biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:caret-right" /></template>
