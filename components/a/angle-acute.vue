<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7_zchb-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7_zchb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:angle-acute" /></template>
