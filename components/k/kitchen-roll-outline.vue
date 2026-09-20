<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxijq36vr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxijq36vr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:kitchen-roll-outline" /></template>
