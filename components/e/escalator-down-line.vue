<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cevw3nbfp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cevw3nbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:escalator-down-line" /></template>
