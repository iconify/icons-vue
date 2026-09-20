<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spdrh7b8d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spdrh7b8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apple-finder" /></template>
