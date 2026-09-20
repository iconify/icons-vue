<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxr8a6byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxr8a6byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:actix" /></template>
