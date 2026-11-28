<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6r9xybbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6r9xybbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hand-heart" /></template>
