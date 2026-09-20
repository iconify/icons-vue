<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbv2_w84w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbv2_w84w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:badoo" /></template>
