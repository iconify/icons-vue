<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz7t8ub8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz7t8ub8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:layer-send-to-back" /></template>
