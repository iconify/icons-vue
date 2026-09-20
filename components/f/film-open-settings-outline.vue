<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fflwz7_rs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fflwz7_rs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-settings-outline" /></template>
