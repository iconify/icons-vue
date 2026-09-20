<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dh8ynxhnb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dh8ynxhnb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:high-voltage-power-fill" /></template>
