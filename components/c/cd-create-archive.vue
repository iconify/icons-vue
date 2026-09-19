<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cr79zmb6s.css';
import '../../css/j/jdsu42b0b.css';
import '../../css/n/n412juyes.css';
import '../../css/v/vk54hubeq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cr79zmb6s"/><circle class="jdsu42b0b"/><path class="n412juyes"/><path class="vk54hubeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:cd-create-archive" /></template>
