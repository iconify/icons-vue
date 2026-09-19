<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2uk39b2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c2uk39b2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:corner-bottom-left" /></template>
