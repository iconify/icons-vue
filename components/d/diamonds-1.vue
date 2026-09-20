<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdh95gmej.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdh95gmej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:diamonds-1" /></template>
