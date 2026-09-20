<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyfts8-ee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyfts8-ee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:information-variant-circle-outline" /></template>
