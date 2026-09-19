<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uk3tahbdx.css';
import '../../css/h/hh66d4b6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk3tahbdx"/><path class="hh66d4b6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:heart-square" /></template>
