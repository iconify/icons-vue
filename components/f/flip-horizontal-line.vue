<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wl0rvqm_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wl0rvqm_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:flip-horizontal-line" /></template>
