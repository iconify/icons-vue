<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2b0_2bec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2b0_2bec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:currency-eur-off" /></template>
