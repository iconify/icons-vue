<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-elkab4b.css';
import '../../css/a/a17nx6bfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-elkab4b"/><path class="a17nx6bfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:arrow-circle-left" /></template>
