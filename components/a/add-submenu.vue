<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucokltb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ucokltb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:add-submenu" /></template>
