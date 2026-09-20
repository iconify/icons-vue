<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nfqqq2-qh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nfqqq2-qh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gender-male-female" /></template>
