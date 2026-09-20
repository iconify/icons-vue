<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uz8ds_9ri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz8ds_9ri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:dribbble-symbol" /></template>
