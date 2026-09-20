<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjxe0hbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjxe0hbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:heat-advisory" /></template>
