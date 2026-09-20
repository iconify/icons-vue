<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgfb9-b1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgfb9-b1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-top-thick" /></template>
