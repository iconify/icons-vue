<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ineco_b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ineco_b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flag-plus-outline" /></template>
