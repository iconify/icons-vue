<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma3s7-bhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma3s7-bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dice-2-fill" /></template>
