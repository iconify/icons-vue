<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gibvwl8bd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gibvwl8bd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-meditation" /></template>
