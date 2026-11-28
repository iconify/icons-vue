<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nt6lf-77j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nt6lf-77j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:bookmark" /></template>
