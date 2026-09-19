<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv-fi9ely.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xv-fi9ely"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:caret-left" /></template>
