<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sg12si0rh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sg12si0rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:cloud-rain-wind" /></template>
