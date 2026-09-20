<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_yi0s_0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_yi0s_0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:logout-variant" /></template>
