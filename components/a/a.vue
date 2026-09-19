<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqlibgbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xqlibgbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:a" /></template>
