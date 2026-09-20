<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i36_azmru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i36_azmru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-minus" /></template>
