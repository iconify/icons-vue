<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf7fidc9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf7fidc9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:backpack-check" /></template>
