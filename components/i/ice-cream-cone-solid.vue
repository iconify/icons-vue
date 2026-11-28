<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo-ev3n8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo-ev3n8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ice-cream-cone-solid" /></template>
