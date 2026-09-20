<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofu24sbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofu24sbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:ito-light" /></template>
