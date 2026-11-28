<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x8pel947e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8pel947e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:contact" /></template>
