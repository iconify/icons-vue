<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i38sq8d7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i38sq8d7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-bottom-detailed-line" /></template>
