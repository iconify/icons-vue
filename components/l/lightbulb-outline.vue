<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scg-lw7vv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scg-lw7vv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-outline" /></template>
