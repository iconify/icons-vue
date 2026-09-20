<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xodhujpzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xodhujpzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-logos:blogger-logo-block" /></template>
