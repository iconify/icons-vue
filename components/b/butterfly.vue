<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjp3d4bta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gjp3d4bta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:butterfly" /></template>
