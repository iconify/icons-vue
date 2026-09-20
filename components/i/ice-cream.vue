<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ang--ib1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ang--ib1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:ice-cream" /></template>
