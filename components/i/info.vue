<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt9-lrb1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="wt9-lrb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:info" /></template>
