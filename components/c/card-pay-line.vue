<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fko8p9bhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fko8p9bhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:card-pay-line" /></template>
