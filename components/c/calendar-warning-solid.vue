<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qzho5zdvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qzho5zdvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:calendar-warning-solid" /></template>
