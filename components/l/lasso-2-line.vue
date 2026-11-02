<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcy_mewmx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcy_mewmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:lasso-2-line" /></template>
