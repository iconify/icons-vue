<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8do_1tjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="n8do_1tjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:hourglass" /></template>
