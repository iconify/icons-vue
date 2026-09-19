<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9w3u4_bj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m9w3u4_bj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-adore-alt-flush" /></template>
