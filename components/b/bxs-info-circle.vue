<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pymkvluxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pymkvluxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-info-circle" /></template>
