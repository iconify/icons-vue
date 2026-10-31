<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8e21kbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8e21kbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:door-fill-round" /></template>
