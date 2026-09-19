<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhzuibcef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qhzuibcef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:jsx-atom" /></template>
