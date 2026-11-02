<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2dkhx_uu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2dkhx_uu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrows-right-line" /></template>
