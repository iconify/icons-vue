<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wty3s35uo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="wty3s35uo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:fast-backward-square-f" /></template>
