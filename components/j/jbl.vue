<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co6v_pfaa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co6v_pfaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:jbl" /></template>
