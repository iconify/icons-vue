<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v88_xacul.css';
import '../../css/w/wtmn1wb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v88_xacul"/><path class="wtmn1wb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:info-circle" /></template>
