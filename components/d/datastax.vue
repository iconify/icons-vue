<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/patyjvp5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="patyjvp5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:datastax" /></template>
