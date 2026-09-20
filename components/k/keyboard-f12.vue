<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od5wrcgjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="od5wrcgjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keyboard-f12" /></template>
