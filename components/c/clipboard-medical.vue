<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8h1qqb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8h1qqb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:clipboard-medical" /></template>
