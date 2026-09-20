<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmr3c33eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmr3c33eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cube-off-outline" /></template>
