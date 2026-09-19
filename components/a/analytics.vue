<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/us8jlr5kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="us8jlr5kr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:analytics" /></template>
