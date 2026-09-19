<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzc2ysb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lzc2ysb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:astonished-face" /></template>
