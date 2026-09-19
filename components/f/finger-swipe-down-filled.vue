<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_vaous8i.css';
import '../../css/y/yze3d2bva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_vaous8i"/><path class="yze3d2bva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:finger-swipe-down-filled" /></template>
