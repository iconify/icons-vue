<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v8u8bubkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v8u8bubkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:co2" /></template>
