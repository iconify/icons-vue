<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co0ju6ars.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co0ju6ars"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-oscillating-off" /></template>
