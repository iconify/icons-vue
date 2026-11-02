<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyu8w6b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyu8w6b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:cellphone-vibration-fill" /></template>
