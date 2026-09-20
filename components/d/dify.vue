<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8yd1s8eo.css';
import '../../css/o/o0bjgebdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8yd1s8eo"/><path class="o0bjgebdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:dify" /></template>
