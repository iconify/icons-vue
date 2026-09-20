<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxh_o_bia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxh_o_bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:analytics" /></template>
