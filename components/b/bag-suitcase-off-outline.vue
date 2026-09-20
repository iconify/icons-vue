<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_a0i2ghy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_a0i2ghy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bag-suitcase-off-outline" /></template>
