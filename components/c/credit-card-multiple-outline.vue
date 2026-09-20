<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if6t8w8ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if6t8w8ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-multiple-outline" /></template>
