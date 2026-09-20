<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iju3si41a.css';
import '../../css/t/tl21czs2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iju3si41a"/><path clip-rule="evenodd" class="tl21czs2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:calculator-2" /></template>
