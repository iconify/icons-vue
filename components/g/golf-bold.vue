<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wabkbdbsx.css';
import '../../css/u/unngw-ben.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wabkbdbsx"/><path class="unngw-ben"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:golf-bold" /></template>
