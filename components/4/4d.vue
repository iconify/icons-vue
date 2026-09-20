<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg_w_7bxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg_w_7bxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:4d" /></template>
