<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlr20m9qu.css';
import '../../css/a/av3hfsqru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rlr20m9qu"/><path class="av3hfsqru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-hyperlink" /></template>
