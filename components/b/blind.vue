<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q23gdwy5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":24};
const content = `<path class="q23gdwy5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:blind" /></template>
