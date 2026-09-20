<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/af9nr9bsw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af9nr9bsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:charger-1-bold" /></template>
