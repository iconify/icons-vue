<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njlgaybpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njlgaybpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fast-forward" /></template>
