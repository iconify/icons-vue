<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz1n2pb7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz1n2pb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:garage-open-variant" /></template>
