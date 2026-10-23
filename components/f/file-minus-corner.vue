<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nql205rcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nql205rcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-minus-corner" /></template>
