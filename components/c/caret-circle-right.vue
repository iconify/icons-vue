<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjy_-lbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjy_-lbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:caret-circle-right" /></template>
