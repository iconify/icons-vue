<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tmlxph0bl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tmlxph0bl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:corner-right-down" /></template>
