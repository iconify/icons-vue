<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgq6ycjyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rgq6ycjyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:battery-bluetooth-variant" /></template>
