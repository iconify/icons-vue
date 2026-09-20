<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7gqgkb3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7gqgkb3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lightbulb-dimmer-10" /></template>
