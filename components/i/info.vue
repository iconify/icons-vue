<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ll1daf0dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ll1daf0dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:info" /></template>
