<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s-by9wblf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s-by9wblf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cube-x" /></template>
