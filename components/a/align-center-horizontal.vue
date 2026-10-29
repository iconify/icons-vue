<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkhgkrtkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fkhgkrtkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-center-horizontal" /></template>
