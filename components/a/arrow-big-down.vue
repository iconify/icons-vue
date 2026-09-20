<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pklshbcld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pklshbcld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-big-down" /></template>
