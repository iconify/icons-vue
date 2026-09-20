<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ltnwmkb5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ltnwmkb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fish" /></template>
