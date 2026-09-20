<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0jh0lg0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0jh0lg0b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-video" /></template>
