<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl7zxybri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl7zxybri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bath-gloss" /></template>
