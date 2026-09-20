<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt1j3xb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt1j3xb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-c-circle" /></template>
