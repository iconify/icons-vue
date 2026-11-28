<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o3jfo9b9j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3jfo9b9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:badge-percent-x" /></template>
