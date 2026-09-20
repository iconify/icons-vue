<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3a2qabhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3a2qabhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:aed" /></template>
