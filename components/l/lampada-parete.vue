<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oq-83c7lb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq-83c7lb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lampada-parete" /></template>
