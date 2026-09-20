<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fyf99sf2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fyf99sf2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:credit-card-remove" /></template>
