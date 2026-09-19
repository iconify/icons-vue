<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wro861b-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wro861b-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:laptop-windows-alt" /></template>
