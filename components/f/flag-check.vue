<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f61n8eakj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f61n8eakj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:flag-check" /></template>
