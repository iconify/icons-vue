<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ww2l8eq6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ww2l8eq6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:font-size-fill" /></template>
