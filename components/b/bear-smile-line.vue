<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dflnx_x8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dflnx_x8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:bear-smile-line" /></template>
