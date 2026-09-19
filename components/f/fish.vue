<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bmn7ynbep.css';
import '../../css/y/yohhqnr3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<circle class="bmn7ynbep"/><path class="yohhqnr3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fish" /></template>
