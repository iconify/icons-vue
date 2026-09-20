<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izgte8b0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="izgte8b0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:bus-1-bold" /></template>
