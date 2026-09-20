<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdfm9_06w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdfm9_06w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:arrow-maximize" /></template>
