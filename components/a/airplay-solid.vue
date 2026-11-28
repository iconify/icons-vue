<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lf_7o0bms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lf_7o0bms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:airplay-solid" /></template>
