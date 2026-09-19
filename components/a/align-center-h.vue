<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wg-xv732t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wg-xv732t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:align-center-h" /></template>
