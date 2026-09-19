<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6w4ul_vh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":527,"height":735};
const content = `<path class="q6w4ul_vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:h-upper-case" /></template>
