<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx7abob1p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx7abob1p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:aib" /></template>
