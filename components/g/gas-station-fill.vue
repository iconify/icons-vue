<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmjidnbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kmjidnbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:gas-station-fill" /></template>
