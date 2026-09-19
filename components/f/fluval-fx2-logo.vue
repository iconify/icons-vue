<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wef4vzbfc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wef4vzbfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:fluval-fx2-logo" /></template>
