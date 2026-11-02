<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-re4_eag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-re4_eag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-nigeria-fill" /></template>
