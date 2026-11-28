<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzv-enb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzv-enb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:hotel-check" /></template>
