<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sqte5-ewe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sqte5-ewe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kodi" /></template>
