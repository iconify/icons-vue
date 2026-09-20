<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf875nbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pf875nbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:castle" /></template>
