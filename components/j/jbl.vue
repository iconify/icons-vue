<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ueax62bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ueax62bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:jbl" /></template>
