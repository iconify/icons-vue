<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5-tgpcat.css';
import '../../css/a/a3mz8kb6e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y5-tgpcat"/><path class="a3mz8kb6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hiking-20" /></template>
