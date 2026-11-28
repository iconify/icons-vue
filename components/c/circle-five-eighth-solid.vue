<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyuvosbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyuvosbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:circle-five-eighth-solid" /></template>
