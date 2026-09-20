<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcfumwk7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bcfumwk7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:gas-station-fuel-petroleum-remix" /></template>
