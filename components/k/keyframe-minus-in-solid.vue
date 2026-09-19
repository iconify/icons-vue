<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te2afuoap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="te2afuoap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:keyframe-minus-in-solid" /></template>
