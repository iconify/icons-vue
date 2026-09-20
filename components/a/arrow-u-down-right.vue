<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyybk_84w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyybk_84w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-u-down-right" /></template>
