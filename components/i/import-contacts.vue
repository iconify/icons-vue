<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/at84vmbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="at84vmbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:import-contacts" /></template>
