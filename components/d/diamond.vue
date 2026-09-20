<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wvc9u6bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wvc9u6bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:diamond" /></template>
