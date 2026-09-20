<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vd4_frbvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vd4_frbvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clipboard-minus-outline" /></template>
