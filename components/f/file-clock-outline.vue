<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmim_580v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmim_580v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-clock-outline" /></template>
