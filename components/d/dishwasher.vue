<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-1j5v11t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-1j5v11t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:dishwasher" /></template>
