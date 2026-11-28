<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cub4olbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cub4olbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:heading-2" /></template>
