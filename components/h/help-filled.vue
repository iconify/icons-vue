<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddjvgw_uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddjvgw_uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:help-filled" /></template>
