<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njivm9bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njivm9bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-scooter" /></template>
