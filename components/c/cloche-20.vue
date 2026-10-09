<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qan-v46oz.css';
import '../../css/r/r-dqwzb9h.css';
import '../../css/s/s2i58ab4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qan-v46oz"/><path class="r-dqwzb9h"/><path class="s2i58ab4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:cloche-20" /></template>
