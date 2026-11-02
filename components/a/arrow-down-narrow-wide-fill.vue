<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz55x2b2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz55x2b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-down-narrow-wide-fill" /></template>
