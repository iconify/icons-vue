<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wocan8bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wocan8bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-rain-wind" /></template>
