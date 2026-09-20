<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nvn0b_bwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nvn0b_bwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:brand-google-solid" /></template>
