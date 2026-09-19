<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pl4nvkpwh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pl4nvkpwh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-h2-switch" /></template>
