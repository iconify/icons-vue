<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz8469k2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz8469k2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:chevrons-down" /></template>
