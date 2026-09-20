<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmi25bcfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmi25bcfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:align-vertical-justify-start" /></template>
