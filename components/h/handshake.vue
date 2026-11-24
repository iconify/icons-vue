<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqizw4bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqizw4bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:handshake" /></template>
