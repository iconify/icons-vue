<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zin2cpjap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":961,"height":960};
const content = `<path class="zin2cpjap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:dominoone" /></template>
