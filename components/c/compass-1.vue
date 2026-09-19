<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/elnfgwwuk.css';
import '../../css/u/u5h-mpcos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="elnfgwwuk"/><circle class="u5h-mpcos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:compass-1" /></template>
