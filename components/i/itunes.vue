<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfxc1rbua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfxc1rbua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:itunes" /></template>
