<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrmzmh_nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrmzmh_nj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:doubanread" /></template>
