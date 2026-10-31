<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhe44_ygs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhe44_ygs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:headphones-gloss" /></template>
