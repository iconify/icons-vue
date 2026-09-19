<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iduj7sbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iduj7sbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:lock" /></template>
