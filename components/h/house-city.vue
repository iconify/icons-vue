<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tgg-4hbjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tgg-4hbjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-city" /></template>
