<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vgcy_mgbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vgcy_mgbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:99designs" /></template>
