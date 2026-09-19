<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/haoji6kic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haoji6kic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:battery-critical" /></template>
