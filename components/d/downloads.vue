<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ids20-b_z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ids20-b_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:downloads" /></template>
