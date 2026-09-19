<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9xz_0btb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s9xz_0btb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-pet-feeder-c1" /></template>
