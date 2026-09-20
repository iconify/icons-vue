<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu6f67tyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu6f67tyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:card-remove" /></template>
