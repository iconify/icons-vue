<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p85cmcb9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p85cmcb9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-vibration-line" /></template>
