<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tq0quybsz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq0quybsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:light-bulb-on" /></template>
