<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lc0_cjb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lc0_cjb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-vertical-fill" /></template>
