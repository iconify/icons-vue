<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rugsg9zlm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rugsg9zlm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-angled-rain" /></template>
