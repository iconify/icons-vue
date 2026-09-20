<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7giz6imy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7giz6imy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:download-network" /></template>
