<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck7do9bfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck7do9bfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:event-seat-outline" /></template>
