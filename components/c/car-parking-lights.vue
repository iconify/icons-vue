<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue9obbc0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue9obbc0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-parking-lights" /></template>
