<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te67u_byu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te67u_byu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chess-bishop" /></template>
