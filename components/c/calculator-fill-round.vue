<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rpsi_yblc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpsi_yblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calculator-fill-round" /></template>
