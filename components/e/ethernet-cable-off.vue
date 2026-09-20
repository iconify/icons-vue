<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ox_ekubta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_ekubta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ethernet-cable-off" /></template>
