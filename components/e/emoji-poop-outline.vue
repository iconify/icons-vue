<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbzico_az.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbzico_az"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:emoji-poop-outline" /></template>
