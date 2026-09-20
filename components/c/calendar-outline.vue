<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p274n3n9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p274n3n9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:calendar-outline" /></template>
