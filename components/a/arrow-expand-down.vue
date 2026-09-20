<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpe_t7bxn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpe_t7bxn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-expand-down" /></template>
