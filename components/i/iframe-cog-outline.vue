<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vg0unkbqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg0unkbqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:iframe-cog-outline" /></template>
