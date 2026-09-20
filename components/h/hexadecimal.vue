<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0c2xwoku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0c2xwoku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:hexadecimal" /></template>
