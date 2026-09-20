<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1y9ezbgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1y9ezbgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-location-outline" /></template>
