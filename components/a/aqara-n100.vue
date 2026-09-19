<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rwiw72nap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rwiw72nap"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-n100" /></template>
