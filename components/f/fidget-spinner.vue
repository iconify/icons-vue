<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hh9z0bo2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hh9z0bo2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:fidget-spinner" /></template>
