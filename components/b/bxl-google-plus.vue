<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxtb5xbbl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxtb5xbbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-google-plus" /></template>
