<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o6ihjbo7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6ihjbo7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-rotate-right-outline" /></template>
