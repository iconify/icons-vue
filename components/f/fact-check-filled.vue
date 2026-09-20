<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulg-93b7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulg-93b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fact-check-filled" /></template>
