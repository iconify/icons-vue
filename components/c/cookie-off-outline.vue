<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r_qj3_bja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_qj3_bja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cookie-off-outline" /></template>
