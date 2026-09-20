<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2-ge_bbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2-ge_bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:effect" /></template>
