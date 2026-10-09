<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/artiuobsj.css';
import '../../css/u/u815dwbzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="artiuobsj"/><path class="u815dwbzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:a-frame-20" /></template>
