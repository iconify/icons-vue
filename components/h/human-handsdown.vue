<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6r7xl_qe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6r7xl_qe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:human-handsdown" /></template>
