<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-_rn-v-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-_rn-v-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-refresh" /></template>
