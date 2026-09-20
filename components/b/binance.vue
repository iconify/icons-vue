<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/an969ebdu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="an969ebdu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:binance" /></template>
