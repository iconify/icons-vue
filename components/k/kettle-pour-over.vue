<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4gawx0pi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4gawx0pi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kettle-pour-over" /></template>
