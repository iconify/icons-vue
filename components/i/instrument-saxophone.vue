<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyr7ylbfe.css';
import '../../css/h/h7wrbubgc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyr7ylbfe"/><path class="h7wrbubgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:instrument-saxophone" /></template>
