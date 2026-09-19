<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wyn63acqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyn63acqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:compressor" /></template>
