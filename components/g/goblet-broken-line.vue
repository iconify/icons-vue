<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zb_4-lefx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zb_4-lefx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:goblet-broken-line" /></template>
