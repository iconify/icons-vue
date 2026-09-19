<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl1-n-b-w.css';
import '../../css/k/k5vk-bbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bl1-n-b-w"/><path class="k5vk-bbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:currency" /></template>
