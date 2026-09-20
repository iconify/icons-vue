<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdex71bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdex71bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bluetooth" /></template>
