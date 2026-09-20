<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wckph6aks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wckph6aks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jsr" /></template>
