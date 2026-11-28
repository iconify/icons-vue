<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unmjk69jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="unmjk69jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bookmark-check" /></template>
