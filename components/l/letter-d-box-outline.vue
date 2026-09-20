<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfowl2b_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfowl2b_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:letter-d-box-outline" /></template>
