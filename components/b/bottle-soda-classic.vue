<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d7h2f57dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7h2f57dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bottle-soda-classic" /></template>
