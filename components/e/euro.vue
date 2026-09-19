<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yat57cxyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yat57cxyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:euro" /></template>
