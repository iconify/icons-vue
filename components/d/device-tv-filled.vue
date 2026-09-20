<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vqn-9kd7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vqn-9kd7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-tv-filled" /></template>
