<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lerzimb4q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lerzimb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:invoice-solid" /></template>
