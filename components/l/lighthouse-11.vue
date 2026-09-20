<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyuod_fzn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="uyuod_fzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:lighthouse-11" /></template>
