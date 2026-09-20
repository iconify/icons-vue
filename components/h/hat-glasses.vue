<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a1y1a3p4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a1y1a3p4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hat-glasses" /></template>
