<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpu-x5tjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpu-x5tjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:caret-down" /></template>
