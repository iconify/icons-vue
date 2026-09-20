<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z256i1gov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z256i1gov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gauge-empty" /></template>
