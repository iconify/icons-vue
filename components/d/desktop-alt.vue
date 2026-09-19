<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wb31hbg0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wb31hbg0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:desktop-alt" /></template>
