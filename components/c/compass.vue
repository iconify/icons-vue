<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dofq-kb2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dofq-kb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:compass" /></template>
