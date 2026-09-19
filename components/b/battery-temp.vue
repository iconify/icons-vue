<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3m2iv_dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3m2iv_dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:battery-temp" /></template>
