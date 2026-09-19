<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spx7v0bsp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spx7v0bsp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-bottom-left-1-thin" /></template>
