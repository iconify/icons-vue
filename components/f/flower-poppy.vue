<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2b7-9e4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2b7-9e4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flower-poppy" /></template>
