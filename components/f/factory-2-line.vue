<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n4_3x3bkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4_3x3bkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:factory-2-line" /></template>
