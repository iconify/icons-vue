<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u6-kewbmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="u6-kewbmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:coins" /></template>
