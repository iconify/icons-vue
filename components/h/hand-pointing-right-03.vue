<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg9unib3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg9unib3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:hand-pointing-right-03" /></template>
