<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pkt06ackd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pkt06ackd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-up-solid" /></template>
