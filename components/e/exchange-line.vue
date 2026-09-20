<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pslpcubsi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pslpcubsi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:exchange-line" /></template>
