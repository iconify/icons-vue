<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rve5_rggl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rve5_rggl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:heart-solid" /></template>
