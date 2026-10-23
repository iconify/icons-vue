<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yg_65gbsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yg_65gbsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grape" /></template>
