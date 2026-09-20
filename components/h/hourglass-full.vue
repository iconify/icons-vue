<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu1dxvbmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu1dxvbmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hourglass-full" /></template>
