<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpwe93btg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpwe93btg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-m-diamond-solid" /></template>
