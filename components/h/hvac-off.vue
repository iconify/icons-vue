<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n5bh-rbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n5bh-rbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hvac-off" /></template>
