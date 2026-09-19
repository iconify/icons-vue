<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vy79ysa6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="vy79ysa6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:inbox" /></template>
