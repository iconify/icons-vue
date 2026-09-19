<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y0n41_jvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0n41_jvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:byd" /></template>
