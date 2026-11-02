<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2q08kypw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f2q08kypw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:corner-down-left-line" /></template>
