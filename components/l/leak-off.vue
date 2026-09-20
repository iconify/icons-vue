<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmh25jbye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmh25jbye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:leak-off" /></template>
