<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eop4rkg4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eop4rkg4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:hexagon-full-solid" /></template>
