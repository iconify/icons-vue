<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0h9l6bvt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0h9l6bvt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:checkbox" /></template>
