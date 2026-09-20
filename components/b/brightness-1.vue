<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iugbchb_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iugbchb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:brightness-1" /></template>
