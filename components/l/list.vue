<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dnosue_qo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnosue_qo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:list" /></template>
