<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jxvl7v3ga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxvl7v3ga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gamepad-right" /></template>
