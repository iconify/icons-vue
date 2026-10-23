<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tja2xlbsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tja2xlbsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hamburger" /></template>
