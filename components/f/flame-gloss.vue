<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xddvxfb5g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xddvxfb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flame-gloss" /></template>
