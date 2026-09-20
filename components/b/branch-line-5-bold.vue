<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrne95bef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nrne95bef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:branch-line-5-bold" /></template>
