<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcg6f8bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcg6f8bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:headset-dock" /></template>
