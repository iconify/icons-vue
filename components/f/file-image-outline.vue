<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo9yh125o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vo9yh125o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:file-image-outline" /></template>
