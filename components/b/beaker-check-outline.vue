<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alk9ttbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alk9ttbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:beaker-check-outline" /></template>
