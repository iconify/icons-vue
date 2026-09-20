<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gja2aab_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gja2aab_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-sound-in-outline" /></template>
