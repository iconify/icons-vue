<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jz_2umrfg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jz_2umrfg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:guitar-pick-outline" /></template>
