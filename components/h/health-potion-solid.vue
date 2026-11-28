<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qu-0zabiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qu-0zabiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:health-potion-solid" /></template>
