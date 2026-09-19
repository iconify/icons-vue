<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci5r98bsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci5r98bsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:align-vertical-center-filled" /></template>
