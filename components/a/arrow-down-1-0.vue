<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp-d-98ah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp-d-98ah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:arrow-down-1-0" /></template>
