<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yob1mji4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yob1mji4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-screenshot" /></template>
