<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmma348sl.css';
import '../../css/y/yh9xo0blb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cmma348sl"/><path class="yh9xo0blb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:corner-up-right-20-bold" /></template>
