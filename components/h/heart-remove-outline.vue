<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/il_g3sssa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="il_g3sssa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heart-remove-outline" /></template>
