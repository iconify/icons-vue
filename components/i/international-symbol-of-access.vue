<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw9hj7r8p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw9hj7r8p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:international-symbol-of-access" /></template>
