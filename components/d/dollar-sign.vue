<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ncf43d60x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncf43d60x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dollar-sign" /></template>
