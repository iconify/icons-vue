<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uo_dnxb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uo_dnxb3j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:chevron-right-filled" /></template>
