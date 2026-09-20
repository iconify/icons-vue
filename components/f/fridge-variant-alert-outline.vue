<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9hj4k0kp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9hj4k0kp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fridge-variant-alert-outline" /></template>
