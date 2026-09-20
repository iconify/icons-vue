<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w3z640blx.css';
import '../../css/a/a65mb4_1c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3z640blx"/><path class="a65mb4_1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:copper-coin-line" /></template>
