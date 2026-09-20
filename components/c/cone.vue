<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm02m8b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm02m8b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cone" /></template>
