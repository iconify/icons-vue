<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p35pwcbqq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="p35pwcbqq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="academicons:google-scholar" /></template>
