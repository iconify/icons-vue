<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_zu7imkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_zu7imkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:boom-gate-up" /></template>
