<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0md93b-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0md93b-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:car-multiple" /></template>
