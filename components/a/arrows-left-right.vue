<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el_nnwvlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="el_nnwvlx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:arrows-left-right" /></template>
