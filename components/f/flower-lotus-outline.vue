<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwn012b_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwn012b_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:flower-lotus-outline" /></template>
