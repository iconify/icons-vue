<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uvtamnw1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uvtamnw1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:dual-sim-signal-4" /></template>
