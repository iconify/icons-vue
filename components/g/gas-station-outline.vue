<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w77x4ze4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w77x4ze4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gas-station-outline" /></template>
