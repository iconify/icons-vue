<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrc_subuv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrc_subuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-bug" /></template>
