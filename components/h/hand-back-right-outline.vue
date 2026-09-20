<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muzwcal8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muzwcal8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hand-back-right-outline" /></template>
