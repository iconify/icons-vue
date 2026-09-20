<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/msac1ccpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="msac1ccpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:house-battery" /></template>
