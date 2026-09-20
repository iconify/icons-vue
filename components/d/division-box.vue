<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vkhg6134t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkhg6134t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:division-box" /></template>
