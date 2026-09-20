<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfbuu8bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfbuu8bri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:coca-cola" /></template>
