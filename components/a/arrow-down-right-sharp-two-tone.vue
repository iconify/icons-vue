<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xown7vyye.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xown7vyye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-right-sharp-two-tone" /></template>
