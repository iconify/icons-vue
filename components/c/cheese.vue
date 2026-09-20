<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he4p34y6k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="he4p34y6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:cheese" /></template>
