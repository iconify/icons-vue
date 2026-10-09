<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxvbekbtz.css';
import '../../css/b/brchb0v7k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wxvbekbtz"/><path class="brchb0v7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:barrel-48-bold" /></template>
