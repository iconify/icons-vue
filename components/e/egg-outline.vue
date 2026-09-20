<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clg852-dm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clg852-dm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:egg-outline" /></template>
