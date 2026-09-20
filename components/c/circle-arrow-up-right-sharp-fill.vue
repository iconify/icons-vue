<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xoatxut6x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xoatxut6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-up-right-sharp-fill" /></template>
