<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c1-t0lb1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="c1-t0lb1w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:landscape-setting-solid" /></template>
