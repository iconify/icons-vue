<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i640xob6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i640xob6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chart4-filled" /></template>
