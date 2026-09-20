<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icxlooygs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icxlooygs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-compass" /></template>
