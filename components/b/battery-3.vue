<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdnuqry3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="kdnuqry3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:battery-3" /></template>
