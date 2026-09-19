<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdzi00bpt.css';
import '../../css/y/y96pjh_pw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdzi00bpt"/><path class="y96pjh_pw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:chart" /></template>
