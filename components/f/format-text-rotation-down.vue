<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pgjv05bkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgjv05bkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-text-rotation-down" /></template>
