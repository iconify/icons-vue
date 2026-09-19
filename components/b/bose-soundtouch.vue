<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5zitl2ao.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5zitl2ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:bose-soundtouch" /></template>
