<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqf5m3bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqf5m3bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-signal-3" /></template>
