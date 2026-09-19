<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpe2ewbnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpe2ewbnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:climbing-wall" /></template>
