<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0rxo6tin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q0rxo6tin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-circle-2-thin" /></template>
