<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/to0cm_bxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to0cm_bxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="weui:close2-filled" /></template>
