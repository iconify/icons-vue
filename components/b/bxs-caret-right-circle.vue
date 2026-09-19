<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf-283b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf-283b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-caret-right-circle" /></template>
