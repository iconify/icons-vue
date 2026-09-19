<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/he-waqbjt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he-waqbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:coin-filled" /></template>
