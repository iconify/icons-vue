<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bkue-o9gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkue-o9gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:arrows-circle-counterclockwise" /></template>
