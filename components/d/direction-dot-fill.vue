<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj25hbbcy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj25hbbcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:direction-dot-fill" /></template>
