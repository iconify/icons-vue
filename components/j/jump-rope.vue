<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thj6iccmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thj6iccmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:jump-rope" /></template>
