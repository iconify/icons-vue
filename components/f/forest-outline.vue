<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxq9tlbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxq9tlbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:forest-outline" /></template>
