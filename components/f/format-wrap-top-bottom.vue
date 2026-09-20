<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dxhqgb70j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxhqgb70j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:format-wrap-top-bottom" /></template>
