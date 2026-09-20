<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbx_tybht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbx_tybht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diamond-24" /></template>
