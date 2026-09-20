<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h0x_rfbyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0x_rfbyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:apple-alt" /></template>
