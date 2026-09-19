<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxnz7abnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxnz7abnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-leaf" /></template>
