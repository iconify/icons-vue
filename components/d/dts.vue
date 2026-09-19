<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udzib8bak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udzib8bak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:dts" /></template>
