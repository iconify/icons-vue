<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xu8ha0bfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xu8ha0bfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fiber-manual-record" /></template>
