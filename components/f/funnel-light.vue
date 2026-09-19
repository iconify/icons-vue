<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npdkz94bu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npdkz94bu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:funnel-light" /></template>
