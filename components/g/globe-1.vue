<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ey338rtxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey338rtxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:globe-1" /></template>
