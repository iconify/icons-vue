<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esul8pbee.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esul8pbee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bulb" /></template>
