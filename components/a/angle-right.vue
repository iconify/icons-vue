<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mlt2f1bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mlt2f1bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:angle-right" /></template>
