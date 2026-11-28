<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppbz2dbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppbz2dbgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cap" /></template>
