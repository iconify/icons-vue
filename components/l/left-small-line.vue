<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zp8tl5bnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zp8tl5bnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:left-small-line" /></template>
