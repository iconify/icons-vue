<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pvskmzb3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvskmzb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fit-to-screen-outline" /></template>
