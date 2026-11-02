<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbsbnxbll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbsbnxbll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:line-squiggle-line" /></template>
