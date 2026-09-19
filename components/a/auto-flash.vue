<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wortgybgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wortgybgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:auto-flash" /></template>
