<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gcc4oqbhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gcc4oqbhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-right2" /></template>
