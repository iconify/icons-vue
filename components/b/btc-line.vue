<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udb9-6b9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udb9-6b9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:btc-line" /></template>
