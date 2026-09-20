<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drot4db0j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drot4db0j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:arrow-downward-circle-line" /></template>
