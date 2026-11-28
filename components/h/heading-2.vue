<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/heo5hlbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="heo5hlbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:heading-2" /></template>
