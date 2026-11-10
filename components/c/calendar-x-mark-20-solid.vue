<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/peon_xbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="peon_xbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:calendar-x-mark-20-solid" /></template>
