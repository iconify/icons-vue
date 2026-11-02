<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lp9gux4fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lp9gux4fj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:bulb-line" /></template>
