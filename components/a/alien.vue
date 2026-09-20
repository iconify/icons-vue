<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g04m7ebjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2};
const content = `<path class="g04m7ebjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:alien" /></template>
