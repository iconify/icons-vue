<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aiyr2hb8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aiyr2hb8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-remove-outline" /></template>
