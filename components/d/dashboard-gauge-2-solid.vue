<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ggwmqsbrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ggwmqsbrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:dashboard-gauge-2-solid" /></template>
