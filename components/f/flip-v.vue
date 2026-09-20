<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9dxgt5kk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r9dxgt5kk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:flip-v" /></template>
