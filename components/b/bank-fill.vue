<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie7qaeb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie7qaeb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bank-fill" /></template>
