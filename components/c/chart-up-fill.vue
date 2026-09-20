<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7mqvj90c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i7mqvj90c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-up-fill" /></template>
