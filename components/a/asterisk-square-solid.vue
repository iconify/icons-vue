<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmk1owber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmk1owber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:asterisk-square-solid" /></template>
