<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncsgg5f8g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncsgg5f8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:bath-solid" /></template>
