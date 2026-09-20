<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eiq64yb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eiq64yb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ios-share" /></template>
