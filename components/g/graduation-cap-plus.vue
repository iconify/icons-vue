<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n07ofsb8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n07ofsb8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:graduation-cap-plus" /></template>
