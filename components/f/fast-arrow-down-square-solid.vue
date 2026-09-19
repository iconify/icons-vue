<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o_kkygljr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o_kkygljr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:fast-arrow-down-square-solid" /></template>
