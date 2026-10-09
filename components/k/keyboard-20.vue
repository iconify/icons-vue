<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z5p77gmzy.css';
import '../../css/x/xetxy-b7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z5p77gmzy"/><path class="xetxy-b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:keyboard-20" /></template>
