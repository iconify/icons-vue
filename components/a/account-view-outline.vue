<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3bzt_gyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y3bzt_gyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:account-view-outline" /></template>
