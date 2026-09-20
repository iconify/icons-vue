<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvimm4bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvimm4bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-round-outline" /></template>
