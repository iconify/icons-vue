<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3t04tbfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3t04tbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:air-conditioner-check" /></template>
