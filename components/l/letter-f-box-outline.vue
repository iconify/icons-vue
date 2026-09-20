<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gszr41b3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gszr41b3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-f-box-outline" /></template>
