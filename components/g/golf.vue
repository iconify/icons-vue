<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn17ebcuh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yn17ebcuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:golf" /></template>
