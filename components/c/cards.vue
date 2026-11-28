<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzop4oy-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzop4oy-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cards" /></template>
